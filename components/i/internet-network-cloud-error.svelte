<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcrzu6bic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pcrzu6bic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:internet-network-cloud-error" {...props}></Icon>
