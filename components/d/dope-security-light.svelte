<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8hp5zbid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p8hp5zbid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dope-security-light" {...props}></Icon>
