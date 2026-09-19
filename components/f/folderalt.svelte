<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgx22db5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":896};
const content = `<path class="bgx22db5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:folderalt" {...props}></Icon>
