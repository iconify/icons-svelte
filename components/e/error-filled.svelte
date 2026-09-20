<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mofy_3ahk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mofy_3ahk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:error-filled" {...props}></Icon>
