<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exfxnbbze.css';
import '../../css/p/p1-cy4b1w.css';
import '../../css/a/a1bg4hbvb.css';
import '../../css/h/hv1t0udsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="exfxnbbze"/><circle class="p1-cy4b1w"/><circle class="a1bg4hbvb"/><circle class="hv1t0udsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:chatbubble-ellipses-outline" {...props}></Icon>
