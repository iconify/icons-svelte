<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/ad99r3bgz.css';
import '../../css/b/b_mqzbbbw.css';
import '../../css/j/jr3u5y25z.css';
import '../../css/j/joaj3f0ng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ad99r3bgz"/><path class="b_mqzbbbw"/><path class="jr3u5y25z"/><path class="joaj3f0ng"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-code-broken" {...props}></Icon>
