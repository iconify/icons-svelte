<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfxwozjpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dfxwozjpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ghost-smile-line" {...props}></Icon>
