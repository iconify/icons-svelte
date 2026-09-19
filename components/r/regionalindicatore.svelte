<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlmpmjhlx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mlmpmjhlx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:regionalindicatore" {...props}></Icon>
