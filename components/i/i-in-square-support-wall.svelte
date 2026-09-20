<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu6v7ibol.css';
import '../../css/i/iq2ggzbaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mu6v7ibol"/><path class="iq2ggzbaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:i-in-square-support-wall" {...props}></Icon>
