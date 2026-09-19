<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0v4h2v6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u0v4h2v6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:logo-css3" {...props}></Icon>
