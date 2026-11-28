<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfvns8u-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfvns8u-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:crosshair" {...props}></Icon>
