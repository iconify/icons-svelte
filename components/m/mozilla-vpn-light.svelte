<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl298fbpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xl298fbpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mozilla-vpn-light" {...props}></Icon>
