<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmv1yubuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fmv1yubuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:citibank-dark" {...props}></Icon>
