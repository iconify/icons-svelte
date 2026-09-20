<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/e/efyrmtbde.css';
import '../../css/u/u_07p0rbf.css';
import '../../css/i/ilf33kbod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="efyrmtbde"/><path class="u_07p0rbf"/><path class="ilf33kbod"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:calendar-clock" {...props}></Icon>
