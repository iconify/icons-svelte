<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3psukb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="w3psukb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:html5" {...props}></Icon>
