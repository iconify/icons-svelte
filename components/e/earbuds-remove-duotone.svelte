<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/ty3omhvwk.css';
import '../../css/r/r6_b4-b2z.css';
import '../../css/q/qhwobdb5c.css';
import '../../css/z/zczqaechp.css';
import '../../css/a/aal2wbblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ty3omhvwk"/><path class="r6_b4-b2z"/><path clip-rule="evenodd" class="qhwobdb5c"/><path class="zczqaechp"/><path class="aal2wbblx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:earbuds-remove-duotone" {...props}></Icon>
