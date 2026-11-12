<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_ij37bly.css';
import '../../css/c/c3p_xw4dl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r_ij37bly"/><path class="c3p_xw4dl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:acquiremock-dark" {...props}></Icon>
