<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkepnv0au.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":480};
const content = `<path class="qkepnv0au"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:dialpad" {...props}></Icon>
