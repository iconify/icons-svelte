<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/uyl-ddcwz.css';
import '../../css/m/mzfdfjbcp.css';
import '../../css/e/e4ii85bpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uyl-ddcwz"/><path clip-rule="evenodd" class="mzfdfjbcp"/><path class="e4ii85bpa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:calendar-fill" {...props}></Icon>
