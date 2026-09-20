<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or-6ds2_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="or-6ds2_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:airplay-video" {...props}></Icon>
