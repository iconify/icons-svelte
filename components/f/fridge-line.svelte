<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzgt7sboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzgt7sboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fridge-line" {...props}></Icon>
