<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4n4ezpvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4n4ezpvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:restart-off" {...props}></Icon>
