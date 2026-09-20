<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l97ms5bsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l97ms5bsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:payload-light" {...props}></Icon>
