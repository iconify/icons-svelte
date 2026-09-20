<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbgw_bblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sbgw_bblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:clipable-dark" {...props}></Icon>
