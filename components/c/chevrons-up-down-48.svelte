<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw67kyv5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nw67kyv5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevrons-up-down-48" {...props}></Icon>
