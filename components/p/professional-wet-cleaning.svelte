<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dkzh7xq6v.css';
import '../../css/j/j3xy0pb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dkzh7xq6v"/><path class="j3xy0pb0u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ginetex:professional-wet-cleaning" {...props}></Icon>
