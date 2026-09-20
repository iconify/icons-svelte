<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x706t8bpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="x706t8bpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:read" {...props}></Icon>
