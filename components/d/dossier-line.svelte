<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxrv5xbkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxrv5xbkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:dossier-line" {...props}></Icon>
