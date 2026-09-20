<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0u9rabbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="n0u9rabbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:global-plant" {...props}></Icon>
