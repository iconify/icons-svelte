<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ald7zq9it.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ald7zq9it"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:markdown-mdx" {...props}></Icon>
