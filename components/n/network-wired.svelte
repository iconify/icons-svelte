<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aele89k-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="aele89k-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:network-wired" {...props}></Icon>
