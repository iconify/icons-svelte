<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xve8_cc1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xve8_cc1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:microsoft-copilot-legacy" {...props}></Icon>
