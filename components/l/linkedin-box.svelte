<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rywumhb7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="rywumhb7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:linkedin-box" {...props}></Icon>
