<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lws288b7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lws288b7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:camera-switch-outline" {...props}></Icon>
