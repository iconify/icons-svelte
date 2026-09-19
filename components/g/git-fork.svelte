<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/a/a4fel-blc.css';
import '../../css/h/hxl5el8-f.css';
import '../../css/o/oy-e8-1zv.css';
import '../../css/t/twh1bab_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><circle class="a4fel-blc"/><circle class="hxl5el8-f"/><circle class="oy-e8-1zv"/><path class="twh1bab_z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:git-fork" {...props}></Icon>
