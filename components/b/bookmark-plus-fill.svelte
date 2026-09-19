<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6kk1bc2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x6kk1bc2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:bookmark-plus-fill" {...props}></Icon>
