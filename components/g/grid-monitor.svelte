<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/h/hvr24jb0v.css';
import '../../css/i/ifgj5l01l.css';
import '../../css/m/m1i0b5bdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="hvr24jb0v"/><path class="ifgj5l01l"/><path class="m1i0b5bdj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:grid-monitor" {...props}></Icon>
