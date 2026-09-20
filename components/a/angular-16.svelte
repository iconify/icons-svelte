<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhvg8jryb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xhvg8jryb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:angular-16" {...props}></Icon>
