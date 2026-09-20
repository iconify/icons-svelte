<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/b/bl3rrbclu.css';
import '../../css/j/joznk2bze.css';
import '../../css/v/vhm0j7bqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bl3rrbclu"/><path class="joznk2bze"/><path class="vhm0j7bqv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:biohazard-off" {...props}></Icon>
