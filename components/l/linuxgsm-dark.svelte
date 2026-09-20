<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itjds7n3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="itjds7n3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:linuxgsm-dark" {...props}></Icon>
