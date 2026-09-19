<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/u/u-8x99uis.css';
import '../../css/h/h10cebcqu.css';
import '../../css/n/nptw7vb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="u-8x99uis"/><path class="h10cebcqu"/><path class="nptw7vb_f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:board-math" {...props}></Icon>
