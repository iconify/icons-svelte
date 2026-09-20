<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4rohbeuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w4rohbeuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:kiss-beam-solid" {...props}></Icon>
