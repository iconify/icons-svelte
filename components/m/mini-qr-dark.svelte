<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrimst9bg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vrimst9bg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mini-qr-dark" {...props}></Icon>
