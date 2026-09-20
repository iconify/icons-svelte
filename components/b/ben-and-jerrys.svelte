<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fka5i5bun.css';
import '../../css/w/wfbp_rb6j.css';
import '../../css/e/ew1brccxv.css';
import '../../css/n/nk2ku8bgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":290,"height":85};
const content = `<path class="fka5i5bun"/><path class="wfbp_rb6j"/><path class="ew1brccxv"/><path class="nk2ku8bgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ben-and-jerrys" {...props}></Icon>
