<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bsp_i4bhb.css';
import '../../css/b/bh5i2pbed.css';
import '../../css/e/egneazb5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="bsp_i4bhb"/><path class="bh5i2pbed"/><path class="egneazb5l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:file-magnifying-glass" {...props}></Icon>
