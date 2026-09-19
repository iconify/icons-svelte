<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa8hv5m4d.css';
import '../../css/x/xn18y8bul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pa8hv5m4d"/><rect class="xn18y8bul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:margin-top-filled" {...props}></Icon>
