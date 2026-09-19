<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/val3symhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="val3symhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:hand-point-left" {...props}></Icon>
