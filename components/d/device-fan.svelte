<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzxji-0-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="gzxji-0-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:device-fan" {...props}></Icon>
