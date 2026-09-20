<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpk0xfhsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpk0xfhsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:karakeep" {...props}></Icon>
