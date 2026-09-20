<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl_cnabsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xl_cnabsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextdns-dark" {...props}></Icon>
