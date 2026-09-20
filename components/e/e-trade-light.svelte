<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp2db-b0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mp2db-b0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:e-trade-light" {...props}></Icon>
