<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj3f72bbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vj3f72bbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:hash-gloss" {...props}></Icon>
