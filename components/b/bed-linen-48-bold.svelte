<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe70pmbug.css';
import '../../css/a/aordspgcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xe70pmbug"/><path class="aordspgcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bed-linen-48-bold" {...props}></Icon>
