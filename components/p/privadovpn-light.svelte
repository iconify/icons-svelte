<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su0c4kbpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="su0c4kbpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:privadovpn-light" {...props}></Icon>
