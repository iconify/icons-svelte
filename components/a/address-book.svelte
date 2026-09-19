<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsiwd6bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="tsiwd6bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:address-book" {...props}></Icon>
