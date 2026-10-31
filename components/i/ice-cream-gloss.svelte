<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwp9_9bow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwp9_9bow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:ice-cream-gloss" {...props}></Icon>
