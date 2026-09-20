<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccqvq0_7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ccqvq0_7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:heart-rate-pulse-graph-solid" {...props}></Icon>
