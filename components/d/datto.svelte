<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrpae2brd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrpae2brd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:datto" {...props}></Icon>
