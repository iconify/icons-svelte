<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0cx09bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0cx09bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:globe-lock" {...props}></Icon>
