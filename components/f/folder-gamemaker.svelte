<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l47nr7bbh.css';
import '../../css/j/j3d0l-bhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l47nr7bbh"/><path class="j3d0l-bhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-gamemaker" {...props}></Icon>
