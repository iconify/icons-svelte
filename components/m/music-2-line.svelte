<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ingnvbcuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ingnvbcuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:music-2-line" {...props}></Icon>
