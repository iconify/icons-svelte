<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijxlat0tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijxlat0tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-woman-hijab-solid" {...props}></Icon>
