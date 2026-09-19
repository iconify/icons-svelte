<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl4di9mpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="fl4di9mpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:red-river" {...props}></Icon>
