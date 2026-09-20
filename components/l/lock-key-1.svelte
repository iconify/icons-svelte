<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/u/ub8zy0l2v.css';
import '../../css/v/vnkm8eb0d.css';
import '../../css/c/cl2yen-js.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ub8zy0l2v"/><path class="vnkm8eb0d"/><path class="cl2yen-js"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:lock-key-1" {...props}></Icon>
