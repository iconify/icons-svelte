<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rgk1ydrjl.css';
import '../../css/m/md5v2cc2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="rgk1ydrjl"/><path class="md5v2cc2g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:building" {...props}></Icon>
