<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p40nu0x8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p40nu0x8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:editor-align-left" {...props}></Icon>
