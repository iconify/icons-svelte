<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj37qhm-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rj37qhm-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-timer" {...props}></Icon>
