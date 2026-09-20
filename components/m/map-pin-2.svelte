<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwg6h_bva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwg6h_bva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:map-pin-2" {...props}></Icon>
