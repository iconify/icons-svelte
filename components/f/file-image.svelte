<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhix2wr0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="yhix2wr0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:file-image" {...props}></Icon>
