<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/i/i4hho8ioh.css';
import '../../css/w/wt2sl3biy.css';
import '../../css/n/nuq8w1bat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="i4hho8ioh"/><path class="wt2sl3biy"/><path clip-rule="evenodd" class="nuq8w1bat"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:hard-drive-sharp-duotone" {...props}></Icon>
