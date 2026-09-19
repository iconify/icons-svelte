<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efn51qbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="efn51qbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chevron-sort-down" {...props}></Icon>
