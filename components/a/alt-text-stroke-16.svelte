<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko5onlbse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ko5onlbse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:alt-text-stroke-16" {...props}></Icon>
