<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epy770bkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="epy770bkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:bookmark-x-fill" {...props}></Icon>
