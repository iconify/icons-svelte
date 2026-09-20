<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfg_v3xsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfg_v3xsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:omada-cloud" {...props}></Icon>
