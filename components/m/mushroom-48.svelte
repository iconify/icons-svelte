<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfyu3jekb.css';
import '../../css/f/fc-7_47pi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yfyu3jekb"/><path class="fc-7_47pi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mushroom-48" {...props}></Icon>
