<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy5yt7bte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cy5yt7bte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:filetype-sass" {...props}></Icon>
