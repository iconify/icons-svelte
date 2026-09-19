<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vbysqvbca.css';
import '../../css/h/hc6km55hv.css';
import '../../css/t/t42vibcgb.css';
import '../../css/r/rx7y-rb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vbysqvbca"/><path clip-rule="evenodd" class="hc6km55hv"/><path class="t42vibcgb"/><path clip-rule="evenodd" class="rx7y-rb9m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blood-cells-24px" {...props}></Icon>
