<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp3swzbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="qp3swzbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:arrow-crossover-right" {...props}></Icon>
