<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0wghy3zj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0wghy3zj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:folder-tree" {...props}></Icon>
