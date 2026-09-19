<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuwx2ibae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vuwx2ibae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:adobe-bridge" {...props}></Icon>
