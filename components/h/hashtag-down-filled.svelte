<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/e0bcgjzbp.css';
import '../../css/n/nqbikvqvq.css';
import '../../css/i/idx0gnbqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="e0bcgjzbp"/><path class="nqbikvqvq"/><path class="idx0gnbqq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:hashtag-down-filled" {...props}></Icon>
