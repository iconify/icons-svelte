<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnk3igu_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnk3igu_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:google-home" {...props}></Icon>
