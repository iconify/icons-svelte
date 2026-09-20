<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8d74bc_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="l8d74bc_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:ink-pen-filled" {...props}></Icon>
