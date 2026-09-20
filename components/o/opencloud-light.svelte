<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bulhn0bpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bulhn0bpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opencloud-light" {...props}></Icon>
