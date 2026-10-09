<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d822ibkfm.css';
import '../../css/p/pmvqjsbun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d822ibkfm"/><path class="pmvqjsbun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:map-route-48-bold" {...props}></Icon>
