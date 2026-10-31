<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgbzj_rvw.css';
import '../../css/y/y862trbtu.css';
import '../../css/e/e11mdeprk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="fgbzj_rvw"/><path class="y862trbtu"/><path class="e11mdeprk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:cefta" {...props}></Icon>
