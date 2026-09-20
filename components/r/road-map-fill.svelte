<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gig7apbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gig7apbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:road-map-fill" {...props}></Icon>
