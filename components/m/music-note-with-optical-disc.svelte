<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz152z8so.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sz152z8so"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:music-note-with-optical-disc" {...props}></Icon>
