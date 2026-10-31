<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc2cd4bto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rc2cd4bto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-plus-corner-round" {...props}></Icon>
