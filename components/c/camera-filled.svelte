<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s07htpbtb.css';
import '../../css/c/cdmk0wbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s07htpbtb"/><path class="cdmk0wbri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:camera-filled" {...props}></Icon>
