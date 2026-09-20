<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kodhyw0ir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kodhyw0ir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:donkey" {...props}></Icon>
