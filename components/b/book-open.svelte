<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qsc1-icia.css';
import '../../css/o/o_xh9pc1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":32};
const content = `<g class="cuyn6tgcc"><path class="qsc1-icia"/><path class="o_xh9pc1a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:book-open" {...props}></Icon>
