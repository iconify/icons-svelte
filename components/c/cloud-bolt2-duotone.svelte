<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/p6bd99rxg.css';
import '../../css/s/s-qsbubff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p6bd99rxg"/><path clip-rule="evenodd" class="s-qsbubff"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cloud-bolt2-duotone" {...props}></Icon>
