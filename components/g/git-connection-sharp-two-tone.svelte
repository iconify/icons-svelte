<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/f/f25gi5bye.css';
import '../../css/g/groubrorl.css';
import '../../css/f/ft5hym8ya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="f25gi5bye"/><path class="groubrorl"/><path class="ft5hym8ya"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:git-connection-sharp-two-tone" {...props}></Icon>
