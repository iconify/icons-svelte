<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuca1sdhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xuca1sdhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:cables-usb-type-c" {...props}></Icon>
