<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/i/iio97lbyc.css';
import '../../css/k/k8hdm7bgr.css';
import '../../css/i/i_drgjvgz.css';
import '../../css/s/ss_z8ac7s.css';
import '../../css/a/ad45zbzbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="y9tr6bcfx"><path class="iio97lbyc"/><path class="k8hdm7bgr"/><path class="i_drgjvgz"/><path class="ss_z8ac7s"/><path class="ad45zbzbj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:circle-more-outline" {...props}></Icon>
