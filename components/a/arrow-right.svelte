<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4ppjuent.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f4ppjuent"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:arrow-right" {...props}></Icon>
