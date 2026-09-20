<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tou73jsic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tou73jsic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:passport-electronic" {...props}></Icon>
