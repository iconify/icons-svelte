<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie1c_b5nl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ie1c_b5nl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:explore-filled" {...props}></Icon>
