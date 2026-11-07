<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hs8rvvlxb.css';
import '../../css/h/h1ru3ab8h.css';
import '../../css/f/f8lgfinhu.css';
import '../../css/g/ge3j4jbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hs8rvvlxb"/><path class="h1ru3ab8h"/><path class="f8lgfinhu"/><path class="ge3j4jbjb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ranking-linear" {...props}></Icon>
