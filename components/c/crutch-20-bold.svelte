<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpntfiblm.css';
import '../../css/e/e2d5-ccdw.css';
import '../../css/s/sahhgmcex.css';
import '../../css/y/ycxbyhbyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xpntfiblm"/><path class="e2d5-ccdw"/><path class="sahhgmcex"/><path class="ycxbyhbyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crutch-20-bold" {...props}></Icon>
