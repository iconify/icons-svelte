<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll5-hlbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ll5-hlbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:admin-comments" {...props}></Icon>
