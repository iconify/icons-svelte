<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kvclpxbgj.css';
import '../../css/k/ka62jfb8e.css';
import '../../css/p/poocn6j4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kvclpxbgj"/><path clip-rule="evenodd" class="ka62jfb8e"/><path class="poocn6j4k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:laptop-download" {...props}></Icon>
