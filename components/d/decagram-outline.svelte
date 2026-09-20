<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvfcm29ft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xvfcm29ft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:decagram-outline" {...props}></Icon>
