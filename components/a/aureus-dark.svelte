<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydaa2vbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ydaa2vbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:aureus-dark" {...props}></Icon>
