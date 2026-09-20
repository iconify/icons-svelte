<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-1tfybvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f-1tfybvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:editor-ordered-list" {...props}></Icon>
