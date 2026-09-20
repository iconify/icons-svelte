<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljv2b8c6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ljv2b8c6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:meshtastic-dark" {...props}></Icon>
