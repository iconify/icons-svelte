<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/o/o7x5x1gvm.css';
import '../../css/a/aggi1x_pz.css';
import '../../css/t/tq4hd5byh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="o7x5x1gvm"/><path class="aggi1x_pz"/><path class="tq4hd5byh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-navigation-sharp-fill" {...props}></Icon>
