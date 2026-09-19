<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r50ruyp5z.css';
import '../../css/u/ua0wb2e8z.css';
import '../../css/q/qack6wv-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="r50ruyp5z"/><path clip-rule="evenodd" class="ua0wb2e8z"/><path class="qack6wv-z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blood-ab-n-outline-24px" {...props}></Icon>
