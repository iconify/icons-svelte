<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd5adsb7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="dd5adsb7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:mars" {...props}></Icon>
