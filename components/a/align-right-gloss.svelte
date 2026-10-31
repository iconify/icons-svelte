<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upwv21bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="upwv21bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:align-right-gloss" {...props}></Icon>
