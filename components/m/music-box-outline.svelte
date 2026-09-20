<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aepqf5neu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aepqf5neu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:music-box-outline" {...props}></Icon>
