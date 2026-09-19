<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/t/tutyhtbtf.css';
import '../../css/l/lvprdxdgh.css';
import '../../css/e/e-1ifub3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><circle class="tutyhtbtf"/><circle class="lvprdxdgh"/><path class="e-1ifub3i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:people" {...props}></Icon>
