<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtiu8tb2k.css';
import '../../css/o/oxin_cb0v.css';
import '../../css/m/mt4ydix1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xtiu8tb2k"/><path class="oxin_cb0v"/><path class="mt4ydix1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:mongoose-wordmark" {...props}></Icon>
