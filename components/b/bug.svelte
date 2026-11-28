<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/wmhbu62zg.css';
import '../../css/a/apxgbkbnj.css';
import '../../css/w/whdadlbkx.css';
import '../../css/r/rioyq6k2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="wmhbu62zg"/><path class="apxgbkbnj"/><path class="whdadlbkx"/><path class="rioyq6k2h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bug" {...props}></Icon>
