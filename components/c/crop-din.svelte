<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/earzy2rdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="earzy2rdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:crop-din" {...props}></Icon>
