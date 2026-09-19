<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvndipqdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lvndipqdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:line-social-fill-16" {...props}></Icon>
