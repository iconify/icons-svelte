<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u96dugbci.css';
import '../../css/j/j-o7--b0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="u96dugbci"/><path class="j-o7--b0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:battery-dead-outline" {...props}></Icon>
