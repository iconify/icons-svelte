<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg96njcks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fg96njcks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:github" {...props}></Icon>
