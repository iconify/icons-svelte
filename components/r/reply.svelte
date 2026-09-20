<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxotj33ea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vxotj33ea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:reply" {...props}></Icon>
