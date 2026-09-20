<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5e2kbc5z.css';
import '../../css/h/ho0k_acab.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/i/ijy0jnbrd.css';
import '../../css/i/i64oqpblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="d5e2kbc5z"/><path class="ho0k_acab"/><g class="ij2x_72vy"><path class="ijy0jnbrd"/><path class="i64oqpblh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:check-mark-button" {...props}></Icon>
