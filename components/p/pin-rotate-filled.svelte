<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxg2wgbpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nxg2wgbpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pin-rotate-filled" {...props}></Icon>
