<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/e/eaguzhbwz.css';
import '../../css/t/tfndbj7co.css';
import '../../css/o/o7w1_wbhx.css';
import '../../css/h/hnovqb_4l.css';
import '../../css/h/h84-17bec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="eaguzhbwz"/><path class="tfndbj7co"/><path class="o7w1_wbhx"/><path class="hnovqb_4l"/><path class="h84-17bec"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:print-text" {...props}></Icon>
