<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/o/owchssbpb.css';
import '../../css/d/dqvcc2bxc.css';
import '../../css/w/wb2sz73pt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="owchssbpb"/><path class="dqvcc2bxc"/><path class="wb2sz73pt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:buy-crypto" {...props}></Icon>
