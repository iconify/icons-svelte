<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfg0gebtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vfg0gebtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:briefcase" {...props}></Icon>
