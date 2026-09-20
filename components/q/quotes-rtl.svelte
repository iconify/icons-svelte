<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8s6fwb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i8s6fwb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:quotes-rtl" {...props}></Icon>
