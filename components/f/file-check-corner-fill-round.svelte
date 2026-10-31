<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/calbeowza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="calbeowza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-check-corner-fill-round" {...props}></Icon>
