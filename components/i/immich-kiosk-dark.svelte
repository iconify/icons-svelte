<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6ahv2bej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m6ahv2bej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:immich-kiosk-dark" {...props}></Icon>
