<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz0cnorym.css';
import '../../css/p/pu7gjm5be.css';
import '../../css/g/gcbpa1m7u.css';
import '../../css/p/p5a3kabtg.css';
import '../../css/f/fkja9wbhy.css';
import '../../css/v/vzsm7w_eg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vz0cnorym"/><path class="pu7gjm5be"/><circle class="gcbpa1m7u"/><path class="p5a3kabtg"/><path class="fkja9wbhy"/><path class="vzsm7w_eg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:bowling" {...props}></Icon>
