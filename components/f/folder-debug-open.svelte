<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov4w-vcsn.css';
import '../../css/n/nhqbeobkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ov4w-vcsn"/><path class="nhqbeobkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-debug-open" {...props}></Icon>
