<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/a/ar6svccon.css';
import '../../css/c/c6yv8di5i.css';
import '../../css/r/r5fi7zbva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><g class="mc2zb0bvp"><path class="ar6svccon"/><path class="c6yv8di5i"/></g><path class="r5fi7zbva"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:link-minimalistic-bold-duotone" {...props}></Icon>
