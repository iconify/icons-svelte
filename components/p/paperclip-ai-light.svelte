<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys5zogbxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ys5zogbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:paperclip-ai-light" {...props}></Icon>
