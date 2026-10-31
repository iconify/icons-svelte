<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajhk2sb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajhk2sb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:luggage-round" {...props}></Icon>
