<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6uk6ybbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6uk6ybbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:gas-station-line" {...props}></Icon>
