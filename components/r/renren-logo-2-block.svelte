<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wko_cm2kp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wko_cm2kp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:renren-logo-2-block" {...props}></Icon>
