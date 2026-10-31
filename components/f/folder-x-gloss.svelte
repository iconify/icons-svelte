<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb2rg5wgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bb2rg5wgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:folder-x-gloss" {...props}></Icon>
