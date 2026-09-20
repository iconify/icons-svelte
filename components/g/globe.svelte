<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfw64ib8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pfw64ib8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:globe" {...props}></Icon>
