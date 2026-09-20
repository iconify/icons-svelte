<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/r/r7eh21bwh.css';
import '../../css/w/wrpl5eb5t.css';
import '../../css/q/qmvky9b5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="r7eh21bwh"/><path class="wrpl5eb5t"/><path class="qmvky9b5j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:crop-image" {...props}></Icon>
