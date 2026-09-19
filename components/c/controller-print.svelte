<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/liu8a-bbg.css';
import '../../css/i/if8c-p6ab.css';
import '../../css/n/nvn0zkb9x.css';
import '../../css/g/gqfbtia_s.css';
import '../../css/j/j7whtobzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="liu8a-bbg"/><path class="if8c-p6ab"/><path clip-rule="evenodd" class="nvn0zkb9x"/><path class="gqfbtia_s"/><path class="j7whtobzs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:controller-print" {...props}></Icon>
