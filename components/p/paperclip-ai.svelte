<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyhp0zbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kyhp0zbri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:paperclip-ai" {...props}></Icon>
