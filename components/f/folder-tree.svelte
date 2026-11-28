<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_viw-bcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_viw-bcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:folder-tree" {...props}></Icon>
