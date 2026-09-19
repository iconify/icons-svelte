<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfshwrkhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vfshwrkhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:map" {...props}></Icon>
