<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7xb_hkno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7xb_hkno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:appnet" {...props}></Icon>
