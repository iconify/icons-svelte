<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcgw_p4gi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="wcgw_p4gi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:emergency-phone-11" {...props}></Icon>
