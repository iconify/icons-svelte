<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cygiloihl.css';
import '../../css/w/wc2xakonk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cygiloihl"/><path class="wc2xakonk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-discord" {...props}></Icon>
