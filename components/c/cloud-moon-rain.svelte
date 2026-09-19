<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zaxzipbah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zaxzipbah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cloud-moon-rain" {...props}></Icon>
