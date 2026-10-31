<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swav2ec8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="swav2ec8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-left-from-line-fill-round" {...props}></Icon>
