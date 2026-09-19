<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv-xs0bgz.css';
import '../../css/h/h8m5eji-v.css';
import '../../css/g/g5ov6kbwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tv-xs0bgz"/><path class="h8m5eji-v"/><path class="g5ov6kbwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:leaffluttering" {...props}></Icon>
