<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u7_8zqbqv.css';
import '../../css/n/n7f3sbidh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="u7_8zqbqv"/><path clip-rule="evenodd" class="n7f3sbidh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:calendar-days-16-solid" {...props}></Icon>
