<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfb-rmbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfb-rmbdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:backtop-rectangle-filled" {...props}></Icon>
