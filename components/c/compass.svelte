<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn3rdabgq.css';
import '../../css/f/fi_q30xur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="fn3rdabgq"/><path class="fi_q30xur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:compass" {...props}></Icon>
