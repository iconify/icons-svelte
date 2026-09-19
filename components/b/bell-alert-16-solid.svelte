<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i0f_5objp.css';
import '../../css/u/u-v275bxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="i0f_5objp"/><path clip-rule="evenodd" class="u-v275bxw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bell-alert-16-solid" {...props}></Icon>
