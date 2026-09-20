<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fox-zjbbr.css';
import '../../css/t/tc50lygvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fox-zjbbr"/><path class="tc50lygvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:reitti-dark" {...props}></Icon>
