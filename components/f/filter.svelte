<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irbofw-4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="irbofw-4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:filter" {...props}></Icon>
