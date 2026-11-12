<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc2htrbqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fc2htrbqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:authman-light" {...props}></Icon>
