<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay3i2kbgt.css';
import '../../css/h/hgch7obpd.css';
import '../../css/h/hs4od_bjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ay3i2kbgt"/><path class="hgch7obpd"/><path class="hs4od_bjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:boat-outline" {...props}></Icon>
