<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcnly3b_c.css';
import '../../css/g/gtz84wbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pcnly3b_c"/><path class="gtz84wbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dji-logbook" {...props}></Icon>
