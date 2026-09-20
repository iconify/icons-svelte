<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr08k9b1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xr08k9b1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alphabet-n-box-outline" {...props}></Icon>
