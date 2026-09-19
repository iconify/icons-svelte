<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/obx052bri.css';
import '../../css/b/b399byz-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="obx052bri"/><path clip-rule="evenodd" class="b399byz-b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:discount-bold" {...props}></Icon>
