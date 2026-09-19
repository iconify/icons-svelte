<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a0bge4cqz.css';
import '../../css/l/l05nigbse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":32};
const content = `<g class="cuyn6tgcc"><path class="a0bge4cqz"/><path class="l05nigbse"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:basket" {...props}></Icon>
