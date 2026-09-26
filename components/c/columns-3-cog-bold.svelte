<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/ql-qkkber.css';
import '../../css/o/ogh3x1btd.css';
import '../../css/r/rt2zemb8t.css';
import '../../css/k/kbty90b-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ql-qkkber"/><path clip-rule="evenodd" class="ogh3x1btd"/><path class="rt2zemb8t"/><path class="kbty90b-x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:columns-3-cog-bold" {...props}></Icon>
