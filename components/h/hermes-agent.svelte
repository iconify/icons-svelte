<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aouuz78vs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aouuz78vs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hermes-agent" {...props}></Icon>
