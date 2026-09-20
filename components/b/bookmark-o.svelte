<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzk3pub-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wzk3pub-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:bookmark-o" {...props}></Icon>
