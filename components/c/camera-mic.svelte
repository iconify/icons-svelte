<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-z7z2qao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="a-z7z2qao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:camera-mic" {...props}></Icon>
