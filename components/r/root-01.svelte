<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/b5pkxmbyt.css';
import '../../css/c/c6kbv1b-p.css';
import '../../css/x/xmu98ub3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="b5pkxmbyt"/><path class="c6kbv1b-p"/><path class="xmu98ub3f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:root-01" {...props}></Icon>
