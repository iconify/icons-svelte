<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgh6tbbcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="kgh6tbbcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-data-trasnfer-vertical-arrow-server-arrows-data-vertical-internet-transfer-network" {...props}></Icon>
