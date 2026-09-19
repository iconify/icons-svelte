<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9gkzib-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b9gkzib-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-adjust" {...props}></Icon>
