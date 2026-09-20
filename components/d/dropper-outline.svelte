<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/e57n2cbti.css';
import '../../css/c/c1yjl09dx.css';
import '../../css/s/sl6xxfjdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="e57n2cbti"/><path class="c1yjl09dx"/><path clip-rule="evenodd" class="sl6xxfjdd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dropper-outline" {...props}></Icon>
