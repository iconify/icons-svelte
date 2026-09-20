<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z60_t-bxa.css';
import '../../css/x/xlzgy4bzl.css';
import '../../css/r/rpvb-o6bq.css';
import '../../css/t/t597itgcw.css';
import '../../css/s/spner8b1a.css';
import '../../css/v/vq_vr4t7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="z60_t-bxa"/><path class="xlzgy4bzl"/><g class="rpvb-o6bq"><path class="t597itgcw"/><path class="spner8b1a"/><path class="vq_vr4t7x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:mending-heart" {...props}></Icon>
