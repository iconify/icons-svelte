<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0b01rbrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0b01rbrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:package-download-corner-round" {...props}></Icon>
