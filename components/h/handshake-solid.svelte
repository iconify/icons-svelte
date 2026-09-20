<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmnso2bxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fmnso2bxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:handshake-solid" {...props}></Icon>
