<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrrj-cbvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rrrj-cbvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:line-h" {...props}></Icon>
