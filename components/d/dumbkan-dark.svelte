<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5igd7btc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x5igd7btc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dumbkan-dark" {...props}></Icon>
