<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1aohj47b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":0.05,"top":0.05};
const content = `<path class="i1aohj47b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:corner-down-left-outline" {...props}></Icon>
