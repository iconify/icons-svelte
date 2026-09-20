<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vrose7bun.css';
import '../../css/y/ylm613c1k.css';
import '../../css/a/a-h5a2b9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vrose7bun"/><path class="ylm613c1k"/><path class="a-h5a2b9l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:contact-line" {...props}></Icon>
