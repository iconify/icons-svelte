<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evbg5bcoz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":279.62,"height":279.9};
const content = `<path class="evbg5bcoz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fpt-play" {...props}></Icon>
