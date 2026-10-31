<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2-d9v4-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l2-d9v4-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:list-sparkle-round" {...props}></Icon>
