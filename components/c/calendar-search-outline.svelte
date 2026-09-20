<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uspsjv9tl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uspsjv9tl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-search-outline" {...props}></Icon>
