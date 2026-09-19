<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwm_mmbgi.css';
import '../../css/h/hwy34kbyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lwm_mmbgi"/><path class="hwy34kbyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-battery-dead" {...props}></Icon>
