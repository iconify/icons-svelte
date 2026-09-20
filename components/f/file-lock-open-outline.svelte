<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj19jgben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nj19jgben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-lock-open-outline" {...props}></Icon>
