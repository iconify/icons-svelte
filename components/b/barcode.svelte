<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l01nldbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l01nldbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:barcode" {...props}></Icon>
