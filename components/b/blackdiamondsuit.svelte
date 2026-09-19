<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgvlc0biq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bgvlc0biq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:blackdiamondsuit" {...props}></Icon>
