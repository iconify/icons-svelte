<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu4o5rbfd.css';
import '../../css/h/ho_37qg1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cu4o5rbfd"/><path class="ho_37qg1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-obsidian-open" {...props}></Icon>
