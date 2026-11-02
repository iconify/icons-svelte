<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4-prbbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4-prbbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:grid-2x2-plus-line" {...props}></Icon>
