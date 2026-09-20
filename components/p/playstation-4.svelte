<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx2nqib3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vx2nqib3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:playstation-4" {...props}></Icon>
