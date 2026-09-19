<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/heavwi7eu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="heavwi7eu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:earth-europe" {...props}></Icon>
