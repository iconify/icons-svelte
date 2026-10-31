<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/j/j4_nmj0ma.css';
import '../../css/n/nktcagb0b.css';
import '../../css/f/fi4q-dntr.css';
import '../../css/t/tba3_6bfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="j4_nmj0ma wm-shadow"/><path class="nktcagb0b wm-shadow"/><path class="fi4q-dntr"/><path class="tba3_6bfv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:arrow-down" {...props}></Icon>
