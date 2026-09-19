<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngt13rb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="ngt13rb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:nfc" {...props}></Icon>
