<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jhegjbgei.css';
import '../../css/c/cm2goxb8k.css';
import '../../css/r/rkhkfhe6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jhegjbgei"/><path clip-rule="evenodd" class="cm2goxb8k"/><path clip-rule="evenodd" class="rkhkfhe6x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:diabetes-measure-24px" {...props}></Icon>
