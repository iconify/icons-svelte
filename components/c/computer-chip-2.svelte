<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/btpk1bcys.css';
import '../../css/m/m76ygirhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path class="btpk1bcys"/><path class="m76ygirhl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:computer-chip-2" {...props}></Icon>
