<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/o/o0iveosml.css';
import '../../css/x/x3gn12ylu.css';
import '../../css/o/ozkkt8zvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="o0iveosml"/><path class="x3gn12ylu"/><path class="ozkkt8zvi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:broken-smartphone-1" {...props}></Icon>
