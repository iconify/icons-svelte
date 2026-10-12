<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z9vtkrbdu.css';
import '../../css/u/uo2ylvp5t.css';
import '../../css/r/rkgl6objd.css';
import '../../css/x/x4ihxui-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><rect class="z9vtkrbdu"/><rect class="uo2ylvp5t"/><path class="rkgl6objd"/><path class="x4ihxui-o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:calendar-days" {...props}></Icon>
