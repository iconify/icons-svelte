<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f95-ijf-n.css';
import '../../css/f/futrw6b2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f95-ijf-n"/><path class="futrw6b2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-pdf" {...props}></Icon>
