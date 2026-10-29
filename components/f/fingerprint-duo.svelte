<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/w4fklccqs.css';
import '../../css/x/x2wfbzbcz.css';
import '../../css/f/fkvw3pbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="w4fklccqs"/><path class="wm-a x2wfbzbcz"/><path class="fkvw3pbgy wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:fingerprint-duo" {...props}></Icon>
