<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3n-2sleg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c3n-2sleg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:editor-position-bottom-left" {...props}></Icon>
