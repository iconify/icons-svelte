<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/c77bytqov.css';
import '../../css/b/bvn-2db2g.css';
import '../../css/d/dvlkv87yt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="c77bytqov"/><path class="bvn-2db2g"/><path class="dvlkv87yt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:pci-card-network" {...props}></Icon>
