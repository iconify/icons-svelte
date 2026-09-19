<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb88n8bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gb88n8bfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:firefox-browser" {...props}></Icon>
