<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu5i0ibdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":456};
const content = `<path class="pu5i0ibdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:lock-open" {...props}></Icon>
