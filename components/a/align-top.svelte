<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/m/mg7aqnbsf.css';
import '../../css/i/i8979pb_i.css';
import '../../css/m/m0f9xo_pb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mg7aqnbsf"/><rect transform="rotate(-90 6 20)" class="i8979pb_i"/><rect transform="rotate(-90 14 16)" class="m0f9xo_pb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:align-top" {...props}></Icon>
