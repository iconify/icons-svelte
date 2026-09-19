<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcd5q2yhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="hcd5q2yhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:braillez" {...props}></Icon>
