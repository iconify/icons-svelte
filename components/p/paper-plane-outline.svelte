<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhzb4-b0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jhzb4-b0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:paper-plane-outline" {...props}></Icon>
