<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/e/ek8eycbfz.css';
import '../../css/b/b4q5icciq.css';
import '../../css/z/zbx2d_b7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="ek8eycbfz"/><path class="b4q5icciq"/><path class="zbx2d_b7p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:print" {...props}></Icon>
