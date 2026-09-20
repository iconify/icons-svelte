<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6bpiubko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6bpiubko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chart-draw-io-filled" {...props}></Icon>
