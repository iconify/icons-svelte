<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/s/siy926dmk.css';
import '../../css/m/mee3dzblk.css';
import '../../css/p/peu007b-y.css';
import '../../css/t/t_wo4ibie.css';
import '../../css/i/ias_7wphn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="siy926dmk wm-deco"/><path class="mee3dzblk wm-deco"/><path class="peu007b-y wm-k"/><path class="t_wo4ibie wm-a"/><path class="ias_7wphn wm-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bookmark-plus-blueprint" {...props}></Icon>
