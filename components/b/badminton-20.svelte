<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fha4pdfyp.css';
import '../../css/r/r9o8-5b4i.css';
import '../../css/e/eng9yvngw.css';
import '../../css/x/xioe6dzyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fha4pdfyp"/><path class="r9o8-5b4i"/><path class="eng9yvngw"/><path class="xioe6dzyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:badminton-20" {...props}></Icon>
