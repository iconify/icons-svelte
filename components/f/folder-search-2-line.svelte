<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlnfd2b4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xlnfd2b4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-search-2-line" {...props}></Icon>
