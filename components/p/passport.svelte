<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/ai4b0kbev.css';
import '../../css/a/al0e8zqyv.css';
import '../../css/s/sdy0koojq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ai4b0kbev"/><path class="al0e8zqyv"/><path clip-rule="evenodd" class="sdy0koojq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:passport" {...props}></Icon>
