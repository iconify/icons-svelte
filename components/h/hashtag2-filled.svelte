<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/ad7wl963m.css';
import '../../css/n/nlcbroobe.css';
import '../../css/z/zzdvaient.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ad7wl963m"/><path class="nlcbroobe"/><path class="zzdvaient"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:hashtag2-filled" {...props}></Icon>
