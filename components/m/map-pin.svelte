<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbnxg3b-j.css';
import '../../css/s/sxj-2bc0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbnxg3b-j wm-k"/><path class="sxj-2bc0x wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:map-pin" {...props}></Icon>
