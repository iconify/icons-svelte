<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir7lnvtyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ir7lnvtyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-excel-2000-light" {...props}></Icon>
