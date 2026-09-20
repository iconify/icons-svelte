<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr-_q9brg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="qr-_q9brg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:menu-hamburger" {...props}></Icon>
