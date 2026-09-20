<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcufg041w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xcufg041w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:analyze-event" {...props}></Icon>
