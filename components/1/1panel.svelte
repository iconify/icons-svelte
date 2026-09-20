<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcz76q0_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mcz76q0_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:1panel" {...props}></Icon>
