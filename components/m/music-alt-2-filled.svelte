<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfc3x4wxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wfc3x4wxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:music-alt-2-filled" {...props}></Icon>
