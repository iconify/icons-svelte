<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj_q1lb9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nj_q1lb9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:exclaimationquestionmark" {...props}></Icon>
