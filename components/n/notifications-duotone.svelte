<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kxgwihb_x.css';
import '../../css/a/afhufubtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kxgwihb_x"/><path class="afhufubtl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:notifications-duotone" {...props}></Icon>
