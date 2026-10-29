<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/a7v63ebic.css';
import '../../css/r/re7s1mb8b.css';
import '../../css/x/xfnzpgbvh.css';
import '../../css/p/pandr5r4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="a7v63ebic"/><path class="re7s1mb8b"/><path class="xfnzpgbvh"/><path class="pandr5r4z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bamboo-duo" {...props}></Icon>
