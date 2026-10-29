<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/woxtt2blm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="woxtt2blm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:heart-handshake-solid" {...props}></Icon>
