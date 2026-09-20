<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_05a9drp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q_05a9drp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:editor-position-top-left" {...props}></Icon>
