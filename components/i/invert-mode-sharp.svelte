<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek96bfbmm.css';
import '../../css/l/lyo-h1s_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ek96bfbmm"/><path class="lyo-h1s_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:invert-mode-sharp" {...props}></Icon>
