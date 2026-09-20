<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfrm27b6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dfrm27b6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:arrow-crossover-right-solid" {...props}></Icon>
