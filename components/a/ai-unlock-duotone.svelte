<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nrtkqwbrh.css';
import '../../css/y/y6umuacnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nrtkqwbrh"/><path class="y6umuacnl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-unlock-duotone" {...props}></Icon>
