<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_dhl2b5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d_dhl2b5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:connector-rhomb-filled" {...props}></Icon>
