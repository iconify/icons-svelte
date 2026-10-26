<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/ghdbiy5at.css';
import '../../css/r/r16iwvw8p.css';
import '../../css/i/i8yxkt2vg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="ghdbiy5at"/><path clip-rule="evenodd" class="r16iwvw8p"/><path class="i8yxkt2vg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:happy-sleepy-outline" {...props}></Icon>
