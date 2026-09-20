<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/w/wy9y5naby.css';
import '../../css/q/qt392mi1w.css';
import '../../css/k/k4p-mx6zk.css';
import '../../css/d/d9tj3eb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="wy9y5naby"/><path class="qt392mi1w"/><path class="k4p-mx6zk"/><path class="d9tj3eb5d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:information-desk" {...props}></Icon>
