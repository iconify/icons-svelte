<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd-qr3i-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cd-qr3i-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:favorite-box-multiple" {...props}></Icon>
