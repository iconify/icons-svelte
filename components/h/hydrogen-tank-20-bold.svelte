<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hat3vrldk.css';
import '../../css/j/jj7ew2vkc.css';
import '../../css/f/fztmdkzpk.css';
import '../../css/z/zbfwylorj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hat3vrldk"/><path class="jj7ew2vkc"/><path class="fztmdkzpk"/><path class="zbfwylorj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-tank-20-bold" {...props}></Icon>
