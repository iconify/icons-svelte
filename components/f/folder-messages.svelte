<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbnjf8b6m.css';
import '../../css/l/la8zlpbmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fbnjf8b6m"/><path class="la8zlpbmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-messages" {...props}></Icon>
