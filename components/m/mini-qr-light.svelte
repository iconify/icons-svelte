<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv2s6nbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rv2s6nbdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mini-qr-light" {...props}></Icon>
