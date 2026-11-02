<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1degvmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bc1degvmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rotate-to-horizontal-line" {...props}></Icon>
