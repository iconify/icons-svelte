<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/l/lrtv4u-dn.css';
import '../../css/i/i4da12bea.css';
import '../../css/h/h38z5cbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lrtv4u-dn"/><path class="i4da12bea"/><path class="h38z5cbna"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-mastercard" {...props}></Icon>
