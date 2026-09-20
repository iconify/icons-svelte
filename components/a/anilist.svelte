<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0y-3vblv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0y-3vblv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:anilist" {...props}></Icon>
