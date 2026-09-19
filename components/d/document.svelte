<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h9t97e2dy.css';
import '../../css/p/p7m4o0kko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":32};
const content = `<g class="cuyn6tgcc"><path class="h9t97e2dy"/><path class="p7m4o0kko"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:document" {...props}></Icon>
