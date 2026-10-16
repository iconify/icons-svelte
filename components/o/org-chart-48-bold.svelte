<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t57i_tbgc.css';
import '../../css/d/ds0h63bwt.css';
import '../../css/m/mfzxk5a_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="t57i_tbgc"/><path class="ds0h63bwt"/><path class="mfzxk5a_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:org-chart-48-bold" {...props}></Icon>
