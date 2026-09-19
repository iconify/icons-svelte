<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd9dtcckh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sd9dtcckh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:push" {...props}></Icon>
