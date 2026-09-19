<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvrpqcbxs.css';
import '../../css/m/m025-fvbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jvrpqcbxs"/><path class="m025-fvbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:connection-signal" {...props}></Icon>
