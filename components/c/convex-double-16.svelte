<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj-ycvb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hj-ycvb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:convex-double-16" {...props}></Icon>
