<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpbaf1bjq.css';
import '../../css/v/vjt9g6_xg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wpbaf1bjq"/><path class="vjt9g6_xg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:palette-48-bold" {...props}></Icon>
