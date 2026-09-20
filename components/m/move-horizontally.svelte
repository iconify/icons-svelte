<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krpodeq0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="krpodeq0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:move-horizontally" {...props}></Icon>
