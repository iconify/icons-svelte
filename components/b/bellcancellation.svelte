<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1d3s3bsn.css';
import '../../css/l/lqbsjrb1w.css';
import '../../css/o/o676dwbcr.css';
import '../../css/u/u-r-ieuow.css';
import '../../css/i/i2d_gzgyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u1d3s3bsn"/><path class="lqbsjrb1w"/><path class="o676dwbcr"/><path class="u-r-ieuow"/><path class="i2d_gzgyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:bellcancellation" {...props}></Icon>
