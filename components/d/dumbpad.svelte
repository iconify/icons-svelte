<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbtomab4q.css';
import '../../css/t/tytji7n_q.css';
import '../../css/e/egb1_lbof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="lbtomab4q"/><path class="tytji7n_q"/><path class="egb1_lbof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dumbpad" {...props}></Icon>
