<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyzb_njoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kyzb_njoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:helm" {...props}></Icon>
