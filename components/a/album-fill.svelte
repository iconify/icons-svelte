<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n193s0b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n193s0b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:album-fill" {...props}></Icon>
