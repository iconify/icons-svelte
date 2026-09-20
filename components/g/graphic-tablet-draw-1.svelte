<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/y/ytz0ut1_u.css';
import '../../css/f/fk4b5hbia.css';
import '../../css/r/rz7rw1bdv.css';
import '../../css/h/hf95ks11o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ytz0ut1_u"/><path class="fk4b5hbia"/><path class="rz7rw1bdv"/><path class="hf95ks11o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:graphic-tablet-draw-1" {...props}></Icon>
