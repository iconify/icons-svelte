<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jn7i9jbvg.css';
import '../../css/w/wf8ebywlw.css';
import '../../css/u/u45aizbtd.css';
import '../../css/u/u3smvcc8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="jn7i9jbvg"/><path class="wf8ebywlw"/><path class="u45aizbtd"/><path class="u3smvcc8q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:exploding-head" {...props}></Icon>
