<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs9w5vowg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hs9w5vowg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:feedbase-dark" {...props}></Icon>
