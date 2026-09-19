<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/h/hxl5el8-f.css';
import '../../css/o/oy-e8-1zv.css';
import '../../css/t/thgdu0bta.css';
import '../../css/t/tk1578ajx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><circle class="hxl5el8-f"/><circle class="oy-e8-1zv"/><circle class="thgdu0bta"/><path class="tk1578ajx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:git-branch" {...props}></Icon>
