<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjvwrkxaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tjvwrkxaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-k-round" {...props}></Icon>
