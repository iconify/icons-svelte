<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8p-h-95k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8p-h-95k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-line-fill-round" {...props}></Icon>
