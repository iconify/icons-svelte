<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t713w4bax.css';
import '../../css/d/d51rrrlde.css';
import '../../css/p/p3poopb-f.css';
import '../../css/i/iom5okjco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t713w4bax"/><path class="d51rrrlde"/><path class="p3poopb-f"/><path class="iom5okjco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:calendar-chevrons-left-duotone" {...props}></Icon>
