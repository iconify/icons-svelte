<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d51d4d4ea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d51d4d4ea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:map-simple-destination-line" {...props}></Icon>
