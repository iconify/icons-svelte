<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjhfi1b1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="qjhfi1b1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:magnet" {...props}></Icon>
