<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq0w_7b_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cq0w_7b_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:hourglass-outline" {...props}></Icon>
