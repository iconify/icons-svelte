<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/filwcgb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="filwcgb8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:list" {...props}></Icon>
