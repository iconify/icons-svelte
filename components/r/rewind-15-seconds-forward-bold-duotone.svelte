<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/ds0znlb8s.css';
import '../../css/t/tcec7mbfa.css';
import '../../css/t/tjh65cbaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ds0znlb8s"/><path class="tcec7mbfa"/><path clip-rule="evenodd" class="tjh65cbaa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rewind-15-seconds-forward-bold-duotone" {...props}></Icon>
