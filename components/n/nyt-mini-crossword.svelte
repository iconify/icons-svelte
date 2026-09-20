<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umjb_uhmw.css';
import '../../css/t/t6ojfgbzo.css';
import '../../css/o/o8-7gvb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="umjb_uhmw"/><path class="t6ojfgbzo"/><path class="o8-7gvb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nyt-mini-crossword" {...props}></Icon>
