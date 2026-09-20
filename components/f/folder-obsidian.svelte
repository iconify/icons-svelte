<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4b_j2glt.css';
import '../../css/h/ho_37qg1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f4b_j2glt"/><path class="ho_37qg1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-obsidian" {...props}></Icon>
