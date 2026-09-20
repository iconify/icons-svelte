<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2ru3b4ba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y2ru3b4ba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:commodore" {...props}></Icon>
