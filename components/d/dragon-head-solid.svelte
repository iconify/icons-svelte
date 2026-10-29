<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/tv42nmbeb.css';
import '../../css/w/wik0hzjja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tv42nmbeb wm-k"/><path class="wik0hzjja wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:dragon-head-solid" {...props}></Icon>
