<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi916br-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pi916br-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cursor-text-fill" {...props}></Icon>
