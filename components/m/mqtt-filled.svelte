<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy3l7hbqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="wy3l7hbqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:mqtt-filled" {...props}></Icon>
