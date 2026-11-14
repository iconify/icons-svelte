<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/d/dvfl3fbbc.css';
import '../../css/q/q7oonn27c.css';
import '../../css/d/d02nshtjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dvfl3fbbc"/><path class="q7oonn27c"/><path class="d02nshtjo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-network" {...props}></Icon>
