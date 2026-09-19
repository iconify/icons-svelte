<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orpr6mbrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="orpr6mbrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:location-pin" {...props}></Icon>
