<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctszb1amv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctszb1amv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pin-line" {...props}></Icon>
