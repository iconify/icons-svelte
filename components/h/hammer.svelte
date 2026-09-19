<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7un0iy0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j7un0iy0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:hammer" {...props}></Icon>
