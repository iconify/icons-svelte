<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b1rx_p1lu.css';
import '../../css/u/uypc25u4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b1rx_p1lu"/><path class="uypc25u4n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:phone-enabled-duotone" {...props}></Icon>
