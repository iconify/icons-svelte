<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yypzf8b8r.css';
import '../../css/f/f-_fxyb8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yypzf8b8r"/><path class="f-_fxyb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:folder-windows-open" {...props}></Icon>
