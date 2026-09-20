<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgvb62whh.css';
import '../../css/f/fb_vjebgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vgvb62whh"/><path class="fb_vjebgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-mail" {...props}></Icon>
