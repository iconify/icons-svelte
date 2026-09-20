<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olhorlhrj.css';
import '../../css/k/k_zqql6xy.css';
import '../../css/n/nhcbp3bdb.css';
import '../../css/d/d8qet0omc.css';
import '../../css/x/xig01du4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="olhorlhrj"/><path class="k_zqql6xy"/><path class="nhcbp3bdb"/><path class="d8qet0omc"/><path class="xig01du4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ente-photos" {...props}></Icon>
