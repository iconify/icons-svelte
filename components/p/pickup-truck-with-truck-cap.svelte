<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbgb-vbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qbgb-vbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pickup-truck-with-truck-cap" {...props}></Icon>
