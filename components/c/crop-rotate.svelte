<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vail75b-l.css';
import '../../css/t/too86x9zd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vail75b-l"/><path class="too86x9zd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:crop-rotate" {...props}></Icon>
