<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj-99yt8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xj-99yt8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:cutlery-stroke-16" {...props}></Icon>
