<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/l/l9wm50sqb.css';
import '../../css/f/flz8mqbuo.css';
import '../../css/v/vura0hvqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="l9wm50sqb"/><path class="flz8mqbuo"/><path class="vura0hvqc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:mail-sparkles-sharp-two-tone" {...props}></Icon>
