<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icpnc-zav.css';
import '../../css/f/fkh-yubxj.css';
import '../../css/j/j61w4jzst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="icpnc-zav"/><path class="fkh-yubxj"/><path class="j61w4jzst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:earth-bold" {...props}></Icon>
