<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si0cvqbui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":408};
const content = `<path class="si0cvqbui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:phone-ring" {...props}></Icon>
