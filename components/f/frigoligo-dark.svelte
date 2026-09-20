<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/la_7fabio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="la_7fabio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frigoligo-dark" {...props}></Icon>
