<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz7wb2t7x.css';
import '../../css/v/vza9gr8cj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fz7wb2t7x"/><path class="vza9gr8cj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:maildev" {...props}></Icon>
