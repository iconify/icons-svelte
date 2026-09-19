<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2-3fe2ip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="t2-3fe2ip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:font" {...props}></Icon>
