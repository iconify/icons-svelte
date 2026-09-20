<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_9vdtigo.css';
import '../../css/e/etu-42buw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x_9vdtigo"/><path class="etu-42buw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:klipper" {...props}></Icon>
