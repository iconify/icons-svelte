<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/y/yhnqlx3ap.css';
import '../../css/j/jpyjlobuf.css';
import '../../css/o/omi2j1bhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="yhnqlx3ap"/><path class="jpyjlobuf"/><path class="omi2j1bhz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:calendar-sparkles-sharp-duotone" {...props}></Icon>
