<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4k47t24h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4k47t24h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-e-square-solid" {...props}></Icon>
