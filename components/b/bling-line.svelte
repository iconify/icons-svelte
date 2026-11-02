<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud11b4uxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ud11b4uxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bling-line" {...props}></Icon>
