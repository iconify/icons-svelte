<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hsw04lgqz.css';
import '../../css/q/qviu0dxdv.css';
import '../../css/m/mm1rimbuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<g class="cuyn6tgcc"><path class="hsw04lgqz"/><path clip-rule="evenodd" class="qviu0dxdv"/><path clip-rule="evenodd" class="mm1rimbuj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:file-media-compact" {...props}></Icon>
