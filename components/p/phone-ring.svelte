<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mtn5hjbmi.css';
import '../../css/g/g93bdwbpy.css';
import '../../css/f/f-4eznb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="mtn5hjbmi"/><path class="g93bdwbpy"/><path clip-rule="evenodd" class="f-4eznb8a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:phone-ring" {...props}></Icon>
