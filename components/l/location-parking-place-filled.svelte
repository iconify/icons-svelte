<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwe1n2brt.css';
import '../../css/g/g_zd9bbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwe1n2brt"/><path class="g_zd9bbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:location-parking-place-filled" {...props}></Icon>
