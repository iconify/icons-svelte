<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg3_8ibzz.css';
import '../../css/e/e9mzgf6-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eg3_8ibzz"/><path class="e9mzgf6-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-markdown-open" {...props}></Icon>
