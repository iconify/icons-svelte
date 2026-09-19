<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbnvaacxi.css';
import '../../css/b/bgnsygbap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tbnvaacxi"/><path class="bgnsygbap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:duplicate" {...props}></Icon>
