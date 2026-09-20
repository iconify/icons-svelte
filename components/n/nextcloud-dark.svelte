<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_omvb_gj.css';
import '../../css/x/xgsv66jjz.css';
import '../../css/k/kg-qgmbsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle clip-rule="evenodd" transform="rotate(-13.286 255.94 255.868)" class="k_omvb_gj"/><path clip-rule="evenodd" class="xgsv66jjz"/><path clip-rule="evenodd" class="kg-qgmbsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-dark" {...props}></Icon>
