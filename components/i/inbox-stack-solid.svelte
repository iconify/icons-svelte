<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nluag3umx.css';
import '../../css/k/kc3f-acmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="nluag3umx"/><path class="kc3f-acmi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:inbox-stack-solid" {...props}></Icon>
