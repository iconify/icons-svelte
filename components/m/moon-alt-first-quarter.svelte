<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u99kuibgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="u99kuibgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-alt-first-quarter" {...props}></Icon>
