<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qi1_q9o5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qi1_q9o5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:golf-round" {...props}></Icon>
