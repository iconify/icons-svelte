<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfu-picse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cfu-picse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:handshake" {...props}></Icon>
