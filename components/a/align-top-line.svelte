<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/m/mg7aqnbsf.css';
import '../../css/a/aix3d_r5g.css';
import '../../css/l/lilq786-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mg7aqnbsf"/><rect transform="rotate(-90 6 20)" class="aix3d_r5g"/><rect transform="rotate(-90 14 16)" class="lilq786-o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:align-top-line" {...props}></Icon>
