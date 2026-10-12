<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vz550iwak.css';
import '../../css/p/p3poopb-f.css';
import '../../css/j/jiqekfbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vz550iwak"/><path class="p3poopb-f"/><path class="jiqekfbcd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:calendar-cog-duotone" {...props}></Icon>
