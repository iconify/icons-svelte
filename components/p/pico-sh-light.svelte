<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jeb48f5_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jeb48f5_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pico-sh-light" {...props}></Icon>
