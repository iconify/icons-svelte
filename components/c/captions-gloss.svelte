<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhfx3acst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhfx3acst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:captions-gloss" {...props}></Icon>
