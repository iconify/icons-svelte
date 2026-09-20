<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3sxgqb8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l3sxgqb8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:editor-item-align-right" {...props}></Icon>
