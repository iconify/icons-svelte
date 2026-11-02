<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3-znrybr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3-znrybr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-line" {...props}></Icon>
