<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu6tghbwj.css';
import '../../css/x/xblsrbb2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qu6tghbwj"/><path class="xblsrbb2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-slides-light" {...props}></Icon>
