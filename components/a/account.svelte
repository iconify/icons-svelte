<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9hqy1byp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":384};
const content = `<path class="r9hqy1byp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:account" {...props}></Icon>
