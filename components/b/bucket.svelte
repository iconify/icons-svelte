<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmshjo7qm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="vmshjo7qm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:bucket" {...props}></Icon>
