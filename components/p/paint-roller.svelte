<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/w/wf1qzqceu.css';
import '../../css/q/qu119kboz.css';
import '../../css/j/jvqy27bgy.css';
import '../../css/f/f8c5uldmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="wf1qzqceu wm-shadow"/><path class="qu119kboz wm-shadow"/><path class="jvqy27bgy"/><path class="f8c5uldmr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:paint-roller" {...props}></Icon>
