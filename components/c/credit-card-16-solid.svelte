<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/syhdgl5vr.css';
import '../../css/y/yytflzz-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="syhdgl5vr"/><path clip-rule="evenodd" class="yytflzz-h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:credit-card-16-solid" {...props}></Icon>
