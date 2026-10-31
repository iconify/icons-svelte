<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pg3t-zkoz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pg3t-zkoz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:quote-left-fill-round" {...props}></Icon>
