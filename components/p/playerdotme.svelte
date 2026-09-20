<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q82i5zb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q82i5zb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:playerdotme" {...props}></Icon>
