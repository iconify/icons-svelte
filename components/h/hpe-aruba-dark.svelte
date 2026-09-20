<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwxc7_b3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nwxc7_b3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hpe-aruba-dark" {...props}></Icon>
