<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxeigen8q.css';
import '../../css/m/m8v2x6bra.css';
import '../../css/m/mqybf2b7x.css';
import '../../css/d/dn7q6_s2o.css';
import '../../css/t/tbn_iwbah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="hxeigen8q"/><path class="m8v2x6bra"/><path class="mqybf2b7x"/><path class="dn7q6_s2o"/><path class="tbn_iwbah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:american-football" {...props}></Icon>
