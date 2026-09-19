<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsl7u1bsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="zsl7u1bsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:handshake-angle" {...props}></Icon>
