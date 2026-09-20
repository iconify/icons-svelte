<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chwsiybmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chwsiybmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flip-vertical-line" {...props}></Icon>
