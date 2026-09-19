<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvzy6fb4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kvzy6fb4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:comment-medical" {...props}></Icon>
