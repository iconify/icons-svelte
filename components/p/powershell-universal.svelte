<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys2i7ybay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ys2i7ybay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:powershell-universal" {...props}></Icon>
