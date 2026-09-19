<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f196jybrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="f196jybrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:film-frames" {...props}></Icon>
