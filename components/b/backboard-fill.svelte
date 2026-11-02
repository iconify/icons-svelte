<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sayqumb8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sayqumb8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:backboard-fill" {...props}></Icon>
