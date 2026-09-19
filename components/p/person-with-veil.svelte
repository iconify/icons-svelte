<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bu46aabrq.css';
import '../../css/l/l56jruo8z.css';
import '../../css/o/oz2x3ph5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="bu46aabrq"/><path class="l56jruo8z"/><path class="oz2x3ph5r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:person-with-veil" {...props}></Icon>
