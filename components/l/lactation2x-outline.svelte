<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgftefcmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cgftefcmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:lactation2x-outline" {...props}></Icon>
