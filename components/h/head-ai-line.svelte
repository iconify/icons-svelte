<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm6ox6bvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lm6ox6bvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:head-ai-line" {...props}></Icon>
