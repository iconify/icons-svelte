<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9bhnkb_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i9bhnkb_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:github-stroke-16" {...props}></Icon>
