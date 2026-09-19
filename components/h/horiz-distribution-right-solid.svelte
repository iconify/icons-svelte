<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l5jrfnb1l.css';
import '../../css/y/yxfs3nbpx.css';
import '../../css/n/nuyjr3i2v.css';
import '../../css/n/nn-_ctbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l5jrfnb1l"/><path class="yxfs3nbpx"/><path class="nuyjr3i2v"/><path class="nn-_ctbfr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:horiz-distribution-right-solid" {...props}></Icon>
