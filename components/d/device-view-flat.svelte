<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9uamdkws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e9uamdkws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:device-view-flat" {...props}></Icon>
