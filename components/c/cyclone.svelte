<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axvwdlb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="axvwdlb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:cyclone" {...props}></Icon>
