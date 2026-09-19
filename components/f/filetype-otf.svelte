<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9d3o1b7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q9d3o1b7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:filetype-otf" {...props}></Icon>
