<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmo9ppb1i.css';
import '../../css/r/rwyjbx_4g.css';
import '../../css/e/ebolgtb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="lmo9ppb1i"><path class="rwyjbx_4g"/><path class="ebolgtb4m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate-color:diagram-up-double" {...props}></Icon>
