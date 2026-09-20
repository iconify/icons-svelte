<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llhn36wnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="llhn36wnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:aeroflot" {...props}></Icon>
