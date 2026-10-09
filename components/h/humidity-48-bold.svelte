<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpqifubxl.css';
import '../../css/b/bscrhu_dt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dpqifubxl"/><path class="bscrhu_dt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:humidity-48-bold" {...props}></Icon>
