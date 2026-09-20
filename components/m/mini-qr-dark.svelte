<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkvb5p1nl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pkvb5p1nl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mini-qr-dark" {...props}></Icon>
