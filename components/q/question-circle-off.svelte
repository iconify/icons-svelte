<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pszy_4b0t.css';
import '../../css/j/j4-krt-9e.css';
import '../../css/v/v2z71xb6c.css';
import '../../css/z/zsuclwbnx.css';
import '../../css/k/kspoj7vnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path class="pszy_4b0t"/><path clip-rule="evenodd" class="j4-krt-9e"/><path clip-rule="evenodd" class="v2z71xb6c"/><path class="zsuclwbnx"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:question-circle-off" {...props}></Icon>
