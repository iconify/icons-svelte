<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/falbdf9et.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="falbdf9et"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:magic" {...props}></Icon>
