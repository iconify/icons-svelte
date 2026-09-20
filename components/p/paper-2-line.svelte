<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt27gzbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wt27gzbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:paper-2-line" {...props}></Icon>
