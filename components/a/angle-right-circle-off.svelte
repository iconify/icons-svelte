<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zq999qbzv.css';
import '../../css/b/b8jrw9ptd.css';
import '../../css/z/zsuclwbnx.css';
import '../../css/k/kspoj7vnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path class="zq999qbzv"/><path class="b8jrw9ptd"/><path class="zsuclwbnx"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:angle-right-circle-off" {...props}></Icon>
