<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5u3xrqiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a5u3xrqiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:palette-fill" {...props}></Icon>
