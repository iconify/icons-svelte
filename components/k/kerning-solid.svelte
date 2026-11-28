<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtmobu58j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtmobu58j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:kerning-solid" {...props}></Icon>
