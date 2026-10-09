<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxvl6gbzy.css';
import '../../css/i/i-5u2oj8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wxvl6gbzy"/><path class="i-5u2oj8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:move-vertical-20" {...props}></Icon>
