<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2jonpb2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t2jonpb2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:favorite-cog-outline" {...props}></Icon>
