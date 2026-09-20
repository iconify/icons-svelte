<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4v2imb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k4v2imb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-meet-light" {...props}></Icon>
