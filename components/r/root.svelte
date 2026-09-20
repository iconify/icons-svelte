<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd-rylbav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vd-rylbav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:root" {...props}></Icon>
