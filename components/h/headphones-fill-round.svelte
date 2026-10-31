<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fngnv_hoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fngnv_hoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:headphones-fill-round" {...props}></Icon>
