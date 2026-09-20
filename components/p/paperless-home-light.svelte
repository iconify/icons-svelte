<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haoyznbav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="haoyznbav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:paperless-home-light" {...props}></Icon>
