<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmtnt-_tb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zmtnt-_tb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:missing" {...props}></Icon>
