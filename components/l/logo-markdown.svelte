<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp2hn9c7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vp2hn9c7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:logo-markdown" {...props}></Icon>
