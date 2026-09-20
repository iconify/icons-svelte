<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-r24r9hl.css';
import '../../css/n/nhqbeobkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f-r24r9hl"/><path class="nhqbeobkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-debug" {...props}></Icon>
