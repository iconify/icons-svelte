<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xemtl5mfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xemtl5mfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:post-it-note-minus" {...props}></Icon>
