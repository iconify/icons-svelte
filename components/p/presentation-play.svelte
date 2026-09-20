<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm_7tdbzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nm_7tdbzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:presentation-play" {...props}></Icon>
