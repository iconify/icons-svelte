<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxzkd_ble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wxzkd_ble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:egghead" {...props}></Icon>
