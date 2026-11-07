<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp7j5gwce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vp7j5gwce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rolling-pin-broken" {...props}></Icon>
