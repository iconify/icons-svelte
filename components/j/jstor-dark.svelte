<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wl3bd5ipw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wl3bd5ipw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jstor-dark" {...props}></Icon>
