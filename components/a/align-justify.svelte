<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vf0x807yc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="vf0x807yc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:align-justify" {...props}></Icon>
