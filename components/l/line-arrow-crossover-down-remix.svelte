<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk1bxfqgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lk1bxfqgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:line-arrow-crossover-down-remix" {...props}></Icon>
