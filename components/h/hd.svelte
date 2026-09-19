<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l50k6bbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="l50k6bbov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:hd" {...props}></Icon>
