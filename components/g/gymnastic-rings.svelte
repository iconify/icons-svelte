<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/n/n2p27uj6g.css';
import '../../css/a/asa4rkbid.css';
import '../../css/r/rpqzuubsh.css';
import '../../css/f/fago55b3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="n2p27uj6g"/><path class="asa4rkbid"/><path class="rpqzuubsh"/><path class="fago55b3x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:gymnastic-rings" {...props}></Icon>
