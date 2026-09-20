<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/j/jszxh1b0i.css';
import '../../css/x/xrsgy2bxo.css';
import '../../css/f/f7d702b9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jszxh1b0i"/><path class="xrsgy2bxo"/><path class="f7d702b9j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:broadcast-sharp-two-tone" {...props}></Icon>
