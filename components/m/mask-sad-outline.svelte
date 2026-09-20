<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i-zq19pwq.css';
import '../../css/q/q8y36zb8b.css';
import '../../css/f/fqw-m9rcd.css';
import '../../css/b/b5q-1142n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i-zq19pwq"/><path class="q8y36zb8b"/><path clip-rule="evenodd" class="fqw-m9rcd"/><path class="b5q-1142n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mask-sad-outline" {...props}></Icon>
