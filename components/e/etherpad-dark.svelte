<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ego17gzid.css';
import '../../css/g/gx13bbcrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ego17gzid"/><path class="gx13bbcrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:etherpad-dark" {...props}></Icon>
