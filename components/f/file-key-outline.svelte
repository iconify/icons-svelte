<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnk3k9x0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xnk3k9x0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-key-outline" {...props}></Icon>
