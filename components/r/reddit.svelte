<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/j/jh71pcbtx.css';
import '../../css/l/lgrgacc6o.css';
import '../../css/b/bhv5jlbzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jh71pcbtx"/><path class="lgrgacc6o"/><path class="bhv5jlbzr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:reddit" {...props}></Icon>
