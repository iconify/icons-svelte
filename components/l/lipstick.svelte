<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekt5e2b3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ekt5e2b3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:lipstick" {...props}></Icon>
