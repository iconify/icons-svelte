<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7v4k9b7n.css';
import '../../css/k/k1yi-x8pw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7v4k9b7n"/><path class="k1yi-x8pw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:analytics-graph-stock" {...props}></Icon>
