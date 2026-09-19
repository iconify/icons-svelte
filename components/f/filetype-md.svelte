<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3t2cs7_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c3t2cs7_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:filetype-md" {...props}></Icon>
