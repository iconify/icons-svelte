<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/ohbc30b4c.css';
import '../../css/l/lsfat4b8k.css';
import '../../css/p/p3poopb-f.css';
import '../../css/n/nmm62xm4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ohbc30b4c"/><path class="lsfat4b8k"/><path class="p3poopb-f"/><path class="nmm62xm4k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:calendar-chevrons-right-duotone" {...props}></Icon>
