<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utmfg3ift.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="utmfg3ift"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:i-cursor" {...props}></Icon>
