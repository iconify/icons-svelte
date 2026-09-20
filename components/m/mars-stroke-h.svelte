<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1z_yzfxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k1z_yzfxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:mars-stroke-h" {...props}></Icon>
