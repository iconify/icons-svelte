<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/roo_fduln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="roo_fduln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:arrow-down" {...props}></Icon>
