<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpva0twia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":512};
const content = `<path class="vpva0twia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:bors" {...props}></Icon>
