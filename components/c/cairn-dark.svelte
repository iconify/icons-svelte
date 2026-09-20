<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yawe7cbzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yawe7cbzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cairn-dark" {...props}></Icon>
