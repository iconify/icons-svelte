<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd0fiy1eq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fd0fiy1eq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mpv" {...props}></Icon>
