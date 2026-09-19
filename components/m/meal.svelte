<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fby4i0qco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":569,"height":680};
const content = `<path class="fby4i0qco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:meal" {...props}></Icon>
