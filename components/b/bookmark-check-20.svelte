<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0v1yf7ii.css';
import '../../css/u/u_sp4-r9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x0v1yf7ii"/><path class="u_sp4-r9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bookmark-check-20" {...props}></Icon>
