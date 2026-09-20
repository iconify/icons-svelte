<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/p/pw7dqg-5z.css';
import '../../css/p/p53xcyb3q.css';
import '../../css/e/e5vqnab3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="pw7dqg-5z"/><path class="p53xcyb3q"/><path class="e5vqnab3e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-area-sharp-two-tone" {...props}></Icon>
