<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec08kobtf.css';
import '../../css/m/mweb-cbkq.css';
import '../../css/x/xtbukpbgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ec08kobtf"/><path class="mweb-cbkq"/><path class="xtbukpbgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:kpi-20" {...props}></Icon>
