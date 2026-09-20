<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6d0cu9gi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a6d0cu9gi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:bed-outline" {...props}></Icon>
