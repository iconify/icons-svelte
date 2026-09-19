<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/prrmoe94x.css';
import '../../css/s/s7ynxw99h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="prrmoe94x"/><path clip-rule="evenodd" class="s7ynxw99h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:magic-wand-outline-24px" {...props}></Icon>
