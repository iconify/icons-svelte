<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk1z52j7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xk1z52j7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:editor-grid-magnet" {...props}></Icon>
