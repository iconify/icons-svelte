<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwm8u_t-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwm8u_t-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:align-bottom" {...props}></Icon>
