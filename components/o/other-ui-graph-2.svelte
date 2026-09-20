<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-lwfi6-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q-lwfi6-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-ui-graph-2" {...props}></Icon>
