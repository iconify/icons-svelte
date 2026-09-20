<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olo123k4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="olo123k4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:paperclip-ai-dark" {...props}></Icon>
