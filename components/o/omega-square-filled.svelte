<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxitu-r0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxitu-r0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:omega-square-filled" {...props}></Icon>
