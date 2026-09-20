<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pr02lwb3m.css';
import '../../css/z/zac9v1r7n.css';
import '../../css/g/g_e5y91es.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="pr02lwb3m"/><path class="zac9v1r7n"/><path clip-rule="evenodd" class="g_e5y91es"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cassette-duotone" {...props}></Icon>
