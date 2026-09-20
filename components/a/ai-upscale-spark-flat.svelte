<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/l/lbwnvfbkt.css';
import '../../css/j/jrt5-m2nc.css';
import '../../css/l/lyssfii6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="lbwnvfbkt"/><path class="jrt5-m2nc"/><path class="lyssfii6o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:ai-upscale-spark-flat" {...props}></Icon>
