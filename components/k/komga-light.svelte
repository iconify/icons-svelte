<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6w7gxzsp.css';
import '../../css/m/mcgtvq47v.css';
import '../../css/g/gjl24ib1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u6w7gxzsp"/><path class="mcgtvq47v"/><path class="gjl24ib1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:komga-light" {...props}></Icon>
