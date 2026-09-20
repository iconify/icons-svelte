<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9x0soozf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q9x0soozf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:aseprite" {...props}></Icon>
