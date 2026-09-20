<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e751k0bvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e751k0bvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pan" {...props}></Icon>
