<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcxfff5pm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcxfff5pm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:analytics-board-graph-line-bold" {...props}></Icon>
