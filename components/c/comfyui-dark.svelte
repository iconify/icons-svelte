<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad9uf7u_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ad9uf7u_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:comfyui-dark" {...props}></Icon>
