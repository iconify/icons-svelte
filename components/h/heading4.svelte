<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mghmurb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mghmurb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:heading4" {...props}></Icon>
