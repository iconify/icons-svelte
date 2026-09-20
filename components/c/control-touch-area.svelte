<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2qjoobli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u2qjoobli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:control-touch-area" {...props}></Icon>
