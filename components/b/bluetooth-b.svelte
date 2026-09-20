<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvfl5p4bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vvfl5p4bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:bluetooth-b" {...props}></Icon>
