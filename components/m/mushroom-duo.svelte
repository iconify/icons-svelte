<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/wgcstei8u.css';
import '../../css/t/tsi5nvbml.css';
import '../../css/i/iycs7wjzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="wgcstei8u"/><path class="tsi5nvbml wm-a"/><path class="iycs7wjzl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:mushroom-duo" {...props}></Icon>
