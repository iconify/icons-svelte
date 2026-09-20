<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hspiz0b0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="hspiz0b0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:emergency-stop" {...props}></Icon>
