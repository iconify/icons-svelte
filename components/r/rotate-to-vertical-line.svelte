<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyls0t1sx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uyls0t1sx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rotate-to-vertical-line" {...props}></Icon>
