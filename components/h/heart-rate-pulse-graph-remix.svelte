<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aogr9_c5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="aogr9_c5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:heart-rate-pulse-graph-remix" {...props}></Icon>
