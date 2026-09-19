<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtghzbbpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rtghzbbpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:ellipsis-vertical-circle-sharp" {...props}></Icon>
