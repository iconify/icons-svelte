<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb4udim1u.css';
import '../../css/i/i1kci5b0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eb4udim1u"/><path class="i1kci5b0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:computers-devices-electronics-mobile-qr-scan" {...props}></Icon>
