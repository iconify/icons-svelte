<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j--st9bsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j--st9bsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-headset" {...props}></Icon>
