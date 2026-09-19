<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvrp96bmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mvrp96bmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:phone-off" {...props}></Icon>
