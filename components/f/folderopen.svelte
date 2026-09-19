<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y93-0lb-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="y93-0lb-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:folderopen" {...props}></Icon>
