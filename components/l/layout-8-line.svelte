<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swaptwbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="swaptwbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-8-line" {...props}></Icon>
