<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpd-v0buh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":24};
const content = `<path class="mpd-v0buh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:replit" {...props}></Icon>
