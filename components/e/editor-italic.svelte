<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp6x7xhme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jp6x7xhme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:editor-italic" {...props}></Icon>
