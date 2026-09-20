<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib3jzhgvb.css';
import '../../css/d/debdggzbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ib3jzhgvb"/><path class="debdggzbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-taskfile" {...props}></Icon>
