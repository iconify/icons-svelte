<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2gdnrblg.css';
import '../../css/l/l8kp85irh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i2gdnrblg"/><path class="l8kp85irh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:caravan-48" {...props}></Icon>
