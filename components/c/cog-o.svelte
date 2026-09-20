<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmx758bjt.css';
import '../../css/g/g6rzu6bev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fmx758bjt"/><path class="g6rzu6bev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:cog-o" {...props}></Icon>
