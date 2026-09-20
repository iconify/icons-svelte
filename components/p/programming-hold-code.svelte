<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/o/o1y6l8rmk.css';
import '../../css/r/r1iymrb_r.css';
import '../../css/d/dwxujfbtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="o1y6l8rmk"/><path class="r1iymrb_r"/><path class="dwxujfbtm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:programming-hold-code" {...props}></Icon>
