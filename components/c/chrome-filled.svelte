<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a3i638fzo.css';
import '../../css/w/w28n6kz3w.css';
import '../../css/l/l7y0kwbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a3i638fzo"/><path class="w28n6kz3w"/><path class="l7y0kwbnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chrome-filled" {...props}></Icon>
