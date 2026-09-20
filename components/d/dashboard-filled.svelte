<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0f9fm8gg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="m0f9fm8gg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:dashboard-filled" {...props}></Icon>
