<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0cf-zb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l0cf-zb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nordlocker-dark" {...props}></Icon>
