<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euz4yigix.css';
import '../../css/x/xrxfll02s.css';
import '../../css/p/p5so3dbgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="euz4yigix"/><path class="xrxfll02s"/><path class="p5so3dbgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:chr" {...props}></Icon>
