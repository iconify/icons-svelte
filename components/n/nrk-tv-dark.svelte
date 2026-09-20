<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-qr9ac1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f-qr9ac1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nrk-tv-dark" {...props}></Icon>
