<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/ufdwcf-0b.css';
import '../../css/b/bekxl5b0t.css';
import '../../css/h/hvzh7jbwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="ufdwcf-0b"/><path clip-rule="evenodd" class="bekxl5b0t"/><path class="hvzh7jbwh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:bell" {...props}></Icon>
