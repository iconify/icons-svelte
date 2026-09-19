<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4o3colkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g4o3colkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:dashboard" {...props}></Icon>
