<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_qdlejmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_qdlejmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bank-off-outline" {...props}></Icon>
