<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stbx0wb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="stbx0wb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-scan" {...props}></Icon>
