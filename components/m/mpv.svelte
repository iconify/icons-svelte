<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqryr30dg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqryr30dg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:mpv" {...props}></Icon>
