<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/u/u2r7s51eh.css';
import '../../css/u/u1ri50b5q.css';
import '../../css/j/j5gpb2bpo.css';
import '../../css/z/zs8cn9m8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="u2r7s51eh"/><path class="u1ri50b5q"/><path class="j5gpb2bpo"/><path class="zs8cn9m8n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mochi" {...props}></Icon>
