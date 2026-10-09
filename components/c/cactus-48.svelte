<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el1pu6btt.css';
import '../../css/d/d4ndp2pgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="el1pu6btt"/><path class="d4ndp2pgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cactus-48" {...props}></Icon>
