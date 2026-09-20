<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvxr66big.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvxr66big"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:music-note-whole" {...props}></Icon>
