<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7ykdnb4c.css';
import '../../css/b/bv8dp7-9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e7ykdnb4c"/><path class="bv8dp7-9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:real-estate-building-1" {...props}></Icon>
