<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftfbryb0n.css';
import '../../css/p/pfc59dpqc.css';
import '../../css/u/ufnun_9wh.css';
import '../../css/u/ucp_klm1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="ftfbryb0n"/><path class="pfc59dpqc"/><path class="ufnun_9wh"/><path class="ucp_klm1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:delete" {...props}></Icon>
