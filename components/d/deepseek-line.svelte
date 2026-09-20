<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq8r70bzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sq8r70bzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:deepseek-line" {...props}></Icon>
