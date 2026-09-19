<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu0f6vbvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":384};
const content = `<path class="vu0f6vbvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:arrow-left" {...props}></Icon>
