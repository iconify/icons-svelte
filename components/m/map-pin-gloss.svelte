<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvi71bchf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvi71bchf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:map-pin-gloss" {...props}></Icon>
