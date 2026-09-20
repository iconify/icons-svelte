<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfkn2s3yl.css';
import '../../css/i/iw3tibb8e.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/o/onxcbabva.css';
import '../../css/l/l-fhgubig.css';
import '../../css/a/a2hu4vb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="yfkn2s3yl"/><path class="iw3tibb8e"/><g class="ij2x_72vy"><path class="onxcbabva"/><path class="l-fhgubig"/><path class="a2hu4vb5y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:rice-ball" {...props}></Icon>
