<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kypqemb_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kypqemb_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:memory-arrow-down" {...props}></Icon>
