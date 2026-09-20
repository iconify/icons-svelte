<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhjw5tknw.css';
import '../../css/f/futrw6b2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hhjw5tknw"/><path class="futrw6b2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-pdf-open" {...props}></Icon>
