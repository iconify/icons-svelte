<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgbim8_qg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgbim8_qg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flashlight-off" {...props}></Icon>
