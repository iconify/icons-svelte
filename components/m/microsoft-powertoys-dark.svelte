<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn776wbmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jn776wbmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-powertoys-dark" {...props}></Icon>
