<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe80ngmuz.css';
import '../../css/a/a0sj_5bhv.css';
import '../../css/r/r_d2c4b7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pe80ngmuz"/><path class="a0sj_5bhv"/><path class="r_d2c4b7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:office-20" {...props}></Icon>
