<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n61ytiddf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n61ytiddf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:gesture-slide-up-filled" {...props}></Icon>
