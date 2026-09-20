<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz46q1bza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fz46q1bza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:immersive-translate" {...props}></Icon>
