<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io2yrxapr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="io2yrxapr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:grid-2x2-x-line" {...props}></Icon>
