<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umb8jtbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umb8jtbsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-flickr-square" {...props}></Icon>
