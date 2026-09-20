<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt4p4mb3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wt4p4mb3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:qrcode-edit" {...props}></Icon>
