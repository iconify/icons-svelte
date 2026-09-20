<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_ulhn1tn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w_ulhn1tn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-meet-dark" {...props}></Icon>
