<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/v/vx462l46d.css';
import '../../css/h/hkedf4c7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="vx462l46d"/><path class="hkedf4c7d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:mountain" {...props}></Icon>
