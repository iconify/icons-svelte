<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fyuh6wb8z.css';
import '../../css/s/s9w9-4b0f.css';
import '../../css/z/zn0vk4bkg.css';
import '../../css/z/zepf_92zz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="fyuh6wb8z"/><path class="s9w9-4b0f"/><path clip-rule="evenodd" class="zn0vk4bkg"/><path class="zepf_92zz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:analytics-bold" {...props}></Icon>
