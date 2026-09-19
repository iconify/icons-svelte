<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfw5puwlc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sfw5puwlc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:bowl-rice" {...props}></Icon>
