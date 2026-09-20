<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9vho9_6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9vho9_6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:music-circle" {...props}></Icon>
