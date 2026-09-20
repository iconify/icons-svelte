<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q36sagidl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q36sagidl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:camera" {...props}></Icon>
