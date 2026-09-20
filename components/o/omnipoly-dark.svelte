<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw1ejmbbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fw1ejmbbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:omnipoly-dark" {...props}></Icon>
