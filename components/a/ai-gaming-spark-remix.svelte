<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_x868q1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r_x868q1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ai-gaming-spark-remix" {...props}></Icon>
