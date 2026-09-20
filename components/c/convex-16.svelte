<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe1kayn5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pe1kayn5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:convex-16" {...props}></Icon>
