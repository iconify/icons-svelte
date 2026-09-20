<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xiy7w4wnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xiy7w4wnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:freedesktopdotorg" {...props}></Icon>
