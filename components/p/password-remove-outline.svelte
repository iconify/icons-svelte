<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv4k8x9qx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wv4k8x9qx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:password-remove-outline" {...props}></Icon>
