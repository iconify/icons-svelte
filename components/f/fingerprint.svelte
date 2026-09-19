<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyz0h_7-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eyz0h_7-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:fingerprint" {...props}></Icon>
