<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlbam1fih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zlbam1fih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:filetype-svg" {...props}></Icon>
