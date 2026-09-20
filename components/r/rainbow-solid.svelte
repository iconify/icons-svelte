<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxx5zlbxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pxx5zlbxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:rainbow-solid" {...props}></Icon>
