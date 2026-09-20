<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8jgw_rfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x8jgw_rfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:google-play-games" {...props}></Icon>
