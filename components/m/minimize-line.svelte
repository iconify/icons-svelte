<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj1v9refi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fj1v9refi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:minimize-line" {...props}></Icon>
