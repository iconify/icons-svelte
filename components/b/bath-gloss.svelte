<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wl7zxybri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wl7zxybri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bath-gloss" {...props}></Icon>
