<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw4gn5mis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw4gn5mis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:gas-station-fill" {...props}></Icon>
