<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgdwhabwq.css';
import '../../css/w/wozco6-eg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgdwhabwq"/><path clip-rule="evenodd" class="wozco6-eg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:globe-ban-filled" {...props}></Icon>
