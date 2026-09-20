<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp9srac5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vp9srac5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:right-fill" {...props}></Icon>
