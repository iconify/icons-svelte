<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc7p41gcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dc7p41gcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:barcode" {...props}></Icon>
