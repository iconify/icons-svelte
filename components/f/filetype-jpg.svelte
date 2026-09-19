<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0c9-dp9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b0c9-dp9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:filetype-jpg" {...props}></Icon>
