<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt4y2qbvi.css';
import '../../css/v/vl-s6tbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wt4y2qbvi"/><path class="vl-s6tbeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openhab" {...props}></Icon>
