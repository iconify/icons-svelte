<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/q6dcbeqzs.css';
import '../../css/q/q0flt88vy.css';
import '../../css/q/qtv77fehd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="q6dcbeqzs"/><path class="q0flt88vy"/><path class="qtv77fehd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:rocket" {...props}></Icon>
