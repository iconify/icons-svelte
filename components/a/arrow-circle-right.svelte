<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki6t-obcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ki6t-obcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:arrow-circle-right" {...props}></Icon>
