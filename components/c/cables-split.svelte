<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/r/r4b2gwbvq.css';
import '../../css/p/p3w2d7x_w.css';
import '../../css/g/geahrbbur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="r4b2gwbvq"/><path class="p3w2d7x_w"/><path class="geahrbbur"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:cables-split" {...props}></Icon>
