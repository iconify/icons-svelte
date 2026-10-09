<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw2_5ib7o.css';
import '../../css/u/ul_8xabfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gw2_5ib7o"/><path class="ul_8xabfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:air-conditioner-48-bold" {...props}></Icon>
