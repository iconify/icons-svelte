<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3ksii2ho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r3ksii2ho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:paperclip" {...props}></Icon>
