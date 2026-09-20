<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xenwn65bw.css';
import '../../css/p/pb3h_qhil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xenwn65bw"/><ellipse class="pb3h_qhil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dolibarr" {...props}></Icon>
