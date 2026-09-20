<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfbg9objp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mfbg9objp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:facebook-messenger-light" {...props}></Icon>
