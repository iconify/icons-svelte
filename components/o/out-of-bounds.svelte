<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2-04zs8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z2-04zs8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:out-of-bounds" {...props}></Icon>
