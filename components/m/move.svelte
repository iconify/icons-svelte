<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf_p8zb0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yf_p8zb0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:move" {...props}></Icon>
