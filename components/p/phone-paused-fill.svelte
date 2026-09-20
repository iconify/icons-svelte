<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypft5mbdm.css';
import '../../css/q/qrqpu7qbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ypft5mbdm"/><path class="qrqpu7qbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:phone-paused-fill" {...props}></Icon>
