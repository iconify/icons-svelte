<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vixpal6lt.css';
import '../../css/p/po4snyb_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vixpal6lt"/><path clip-rule="evenodd" class="po4snyb_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:media-play-fail" {...props}></Icon>
