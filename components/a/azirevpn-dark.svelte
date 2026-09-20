<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpfpgdc2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dpfpgdc2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:azirevpn-dark" {...props}></Icon>
