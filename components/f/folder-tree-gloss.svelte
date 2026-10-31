<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozj561beo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozj561beo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:folder-tree-gloss" {...props}></Icon>
