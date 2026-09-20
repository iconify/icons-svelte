<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvjqh6bpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvjqh6bpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:map-marker-minus" {...props}></Icon>
