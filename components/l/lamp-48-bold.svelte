<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtf397bse.css';
import '../../css/x/xyb5vubsu.css';
import '../../css/w/wwtxgkniu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dtf397bse"/><path class="xyb5vubsu"/><path class="wwtxgkniu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lamp-48-bold" {...props}></Icon>
