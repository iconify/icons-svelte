<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4u8obcgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g4u8obcgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-navigate" {...props}></Icon>
