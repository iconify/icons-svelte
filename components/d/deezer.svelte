<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp3tij6sr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dp3tij6sr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:deezer" {...props}></Icon>
