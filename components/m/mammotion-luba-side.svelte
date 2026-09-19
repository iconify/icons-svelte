<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj-gdebvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xj-gdebvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:mammotion-luba-side" {...props}></Icon>
