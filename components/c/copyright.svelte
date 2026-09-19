<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc6k0ubxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uc6k0ubxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:copyright" {...props}></Icon>
