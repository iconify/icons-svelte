<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un1r_mbsq.css';
import '../../css/x/xffa8bcjg.css';
import '../../css/p/pu1_4vbar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="un1r_mbsq"/><path class="xffa8bcjg"/><path class="pu1_4vbar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:biodiversity-48-bold" {...props}></Icon>
