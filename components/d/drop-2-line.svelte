<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-ni44i5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-ni44i5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:drop-2-line" {...props}></Icon>
