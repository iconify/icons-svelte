<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8jnr3b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":440};
const content = `<path class="n8jnr3b2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:layers-clear" {...props}></Icon>
