<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lrcylirep.css';
import '../../css/b/brk_xacuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="lrcylirep"/><path clip-rule="evenodd" class="brk_xacuh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:device-tablet-16-solid" {...props}></Icon>
