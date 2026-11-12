<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcsewxa-q.css';
import '../../css/t/t6ojfgbzo.css';
import '../../css/z/zj67j_bqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zcsewxa-q"/><path class="t6ojfgbzo"/><path class="zj67j_bqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nyt-mini-crossword" {...props}></Icon>
