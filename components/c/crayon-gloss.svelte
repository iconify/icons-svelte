<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdy44fbrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdy44fbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:crayon-gloss" {...props}></Icon>
