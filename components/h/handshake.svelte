<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncolsybxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="ncolsybxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:handshake" {...props}></Icon>
