<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq_wvc0jz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gq_wvc0jz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:playlist-2-line" {...props}></Icon>
