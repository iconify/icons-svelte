<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrkk89byi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrkk89byi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:leaf-3-line" {...props}></Icon>
