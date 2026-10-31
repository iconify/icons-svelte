<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnm-kh31k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hnm-kh31k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-close-corner-fill-round" {...props}></Icon>
