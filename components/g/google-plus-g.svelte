<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt4uggbee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wt4uggbee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:google-plus-g" {...props}></Icon>
