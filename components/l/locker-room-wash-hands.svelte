<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/m/ml9vscc8q.css';
import '../../css/i/iwxpr45qa.css';
import '../../css/k/k2yb2obuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ml9vscc8q"/><path class="iwxpr45qa"/><path class="k2yb2obuz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:locker-room-wash-hands" {...props}></Icon>
