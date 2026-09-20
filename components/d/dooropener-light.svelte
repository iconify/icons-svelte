<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuj0x4b5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cuj0x4b5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dooropener-light" {...props}></Icon>
