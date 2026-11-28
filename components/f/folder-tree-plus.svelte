<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gff683b6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gff683b6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:folder-tree-plus" {...props}></Icon>
