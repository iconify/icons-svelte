<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd4n9pdfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jd4n9pdfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-068" {...props}></Icon>
