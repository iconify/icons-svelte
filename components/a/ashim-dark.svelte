<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iebr1bctr.css';
import '../../css/r/rv1rqnb3e.css';
import '../../css/b/bote1bc2y.css';
import '../../css/p/pq2uk9bbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iebr1bctr"/><path class="rv1rqnb3e"/><path class="bote1bc2y"/><path class="pq2uk9bbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ashim-dark" {...props}></Icon>
