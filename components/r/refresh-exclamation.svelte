<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wobbg0a8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="wobbg0a8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:refresh-exclamation" {...props}></Icon>
