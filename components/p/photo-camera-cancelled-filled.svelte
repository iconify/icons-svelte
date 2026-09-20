<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfge6sb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pfge6sb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:photo-camera-cancelled-filled" {...props}></Icon>
