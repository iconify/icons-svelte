<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikirpnb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ikirpnb2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kickstarter-light" {...props}></Icon>
