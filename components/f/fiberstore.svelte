<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuntz5arz.css';
import '../../css/l/l9we6spoz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vuntz5arz"/><path class="l9we6spoz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fiberstore" {...props}></Icon>
