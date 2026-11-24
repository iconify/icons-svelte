<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lmgxvzi8r.css';
import '../../css/g/gb4dymbxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="lmgxvzi8r"/><path clip-rule="evenodd" class="gb4dymbxw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:cookie" {...props}></Icon>
