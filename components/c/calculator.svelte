<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq33_dvdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1023};
const content = `<path class="vq33_dvdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:calculator" {...props}></Icon>
