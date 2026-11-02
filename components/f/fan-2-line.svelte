<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffas5gxhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ffas5gxhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fan-2-line" {...props}></Icon>
