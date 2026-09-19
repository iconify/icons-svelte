<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pdoa3kqmg.css';
import '../../css/g/g2l8iqnuw.css';
import '../../css/o/or9nmxbka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="pdoa3kqmg"/><path class="g2l8iqnuw"/><path class="or9nmxbka"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:coin" {...props}></Icon>
