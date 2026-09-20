<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ijq_n3b5x.css';
import '../../css/s/sc-bp--qn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path class="ijq_n3b5x"/><path clip-rule="evenodd" class="sc-bp--qn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:mail-send-envelope-flat" {...props}></Icon>
