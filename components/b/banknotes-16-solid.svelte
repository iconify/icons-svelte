<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/np720wjev.css';
import '../../css/s/s_i9kmlzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="np720wjev"/><path class="s_i9kmlzt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:banknotes-16-solid" {...props}></Icon>
