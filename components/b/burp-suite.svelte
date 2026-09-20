<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvfw3i8xa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvfw3i8xa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:burp-suite" {...props}></Icon>
