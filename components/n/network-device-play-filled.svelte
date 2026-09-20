<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8l48i23l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="r8l48i23l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:network-device-play-filled" {...props}></Icon>
