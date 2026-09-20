<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn94_qbhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="dn94_qbhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-signal-graph-circle-circle-stats-graph-line-beat-heart" {...props}></Icon>
