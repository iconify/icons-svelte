<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8vingdhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g8vingdhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:editor-bold" {...props}></Icon>
