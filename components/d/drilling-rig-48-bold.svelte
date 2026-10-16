<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2o-9ho8x.css';
import '../../css/s/sl_3qvbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x2o-9ho8x"/><path class="sl_3qvbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:drilling-rig-48-bold" {...props}></Icon>
