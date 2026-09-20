<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/setvc4bqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="setvc4bqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:location-filled" {...props}></Icon>
