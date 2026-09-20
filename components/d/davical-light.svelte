<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwjdabcpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jwjdabcpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:davical-light" {...props}></Icon>
