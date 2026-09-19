<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/v71jupb4f.css';
import '../../css/l/lfeo2hbff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":32};
const content = `<g class="cuyn6tgcc"><path class="v71jupb4f"/><path class="lfeo2hbff"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:newspaper" {...props}></Icon>
