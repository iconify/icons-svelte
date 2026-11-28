<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydl5wubsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ydl5wubsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:chart-area-thin" {...props}></Icon>
