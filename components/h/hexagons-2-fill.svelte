<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkb7kz3-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkb7kz3-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hexagons-2-fill" {...props}></Icon>
