<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9--0ac3k.css';
import '../../css/x/xe4gu0bmx.css';
import '../../css/v/ve_wlnb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m9--0ac3k"/><path class="xe4gu0bmx"/><path class="ve_wlnb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mop-20-bold" {...props}></Icon>
