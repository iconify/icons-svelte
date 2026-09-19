<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fmuvdrx2z.css';
import '../../css/o/o9up0vbfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fmuvdrx2z"/><path clip-rule="evenodd" class="o9up0vbfz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:calendar-days-solid" {...props}></Icon>
