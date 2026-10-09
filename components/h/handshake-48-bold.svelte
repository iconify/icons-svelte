<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5mm6ob9l.css';
import '../../css/c/cru7ppb5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w5mm6ob9l"/><path class="cru7ppb5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:handshake-48-bold" {...props}></Icon>
