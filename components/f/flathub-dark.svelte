<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt-v--iiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jt-v--iiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:flathub-dark" {...props}></Icon>
